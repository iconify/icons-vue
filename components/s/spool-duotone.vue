<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ah02ogbhh"/><path clip-rule="evenodd" class="u1mhzubry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spool-duotone" /></template>
<style>
.ah02ogbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7C4.3431 7 3 5.657 3 4C3 2.343 4.3431 1 6 1H12H18C19.6569 1 21 2.343 21 4C21 5.657 19.6569 7 18 7V17C19.6569 17 21 18.343 21 20C21 21.657 19.6569 23 18 23H6C4.3431 23 3 21.657 3 20C3 18.343 4.3431 17 6 17V7Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u1mhzubry {
  fill-rule: evenodd;
  d: path("M6 7C4.6937 7 3.5825 6.165 3.1707 5H20.8293C20.4175 6.165 19.3063 7 18 7H6ZM18 17C19.3063 17 20.4175 17.835 20.8293 19H3.1707C3.5825 17.835 4.6937 17 6 17H18ZM6 12.756L18 9.156V11.244L6 14.844V12.756Z");
}

</style>
