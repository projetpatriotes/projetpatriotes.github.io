<!--
Copyright © 2022 Adnan-Aidan Taha and William Ao
This file is part of "Projet Patriotes".

"Projet Patriotes" is free software: you can redistribute it and/or modify it under the terms
of the GNU General Public License as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

"Projet Patriotes" is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with "Projet Patriotes".
If not, see <https://www.gnu.org/licenses/>.
-->

<template>
  <section id="premiereSection" class="paragraphe">
    <slot />
  </section>
</template>

<style lang="scss">
.paragraphe {
  height: auto;
  padding: 1vw;

  ul {
    padding-left: 1.5vw;
  }

  h1,
  h2,
  h3,
  p,
  li {
    margin-bottom: 0.5rem;
  }
}
</style>
