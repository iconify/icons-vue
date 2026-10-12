<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="utz_jfbmg"/><circle class="ie50qbcyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:saw-blade-sharp" /></template>
<style>
.ie50qbcyb {
  cx: 12px;
  cy: 12px;
  r: 3.25px;
}

.utz_jfbmg {
  d: path("m19.61 12.28l1.01 2.5l.11.28l-.3.03l-1.37.13l-.3.03l-.02.3l-.18 2.69l-.02.3l-.28-.1l-1.3-.48l-.28-.1l-.15.26l-1.32 2.35l-.15.26l-.21-.21l-.97-1l-.21-.21l-.25.17l-2.21 1.54l-.25.17l-.1-.28l-.43-1.32l-.1-.28l-.3.05l-2.65.42l-.3.05l.04-.3l.16-1.37l.04-.3l-.29-.09l-2.57-.76l-.29-.09l.16-.25l.75-1.17l.16-.25l-.22-.2l-1.99-1.81l-.22-.2l.26-.16l1.17-.72l.26-.16l-.11-.28l-1.01-2.5l-.11-.28l.3-.03l1.37-.13l.3-.03l.02-.3l.18-2.69l.02-.3l.28.1l1.3.48l.28.1l.15-.26l1.32-2.35l.15-.26l.21.21l.97 1l.21.21l.25-.17l2.21-1.54l.25-.17l.1.28l.43 1.32l.1.28l.3-.05l2.65-.42l.3-.05l-.04.3l-.16 1.37l-.04.3l.29.09l2.57.76l.29.09l-.16.25l-.75 1.17l-.16.25l.22.2l1.99 1.81l.22.2l-.26.16l-1.17.72l-.26.16z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
