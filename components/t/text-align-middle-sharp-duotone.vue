<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="abaekfnni"/><path clip-rule="evenodd" class="kz7gjnbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-middle-sharp-duotone" /></template>
<style>
.abaekfnni {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2H12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kz7gjnbwy {
  fill-rule: evenodd;
  d: path("M6 9H18V11H6V9ZM6 13H14V15H6V13Z");
}

</style>
