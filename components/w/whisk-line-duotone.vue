<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aj6qckodu"/><path class="n31o93rng"/><path class="jxcwdzb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-line-duotone" /></template>
<style>
.aj6qckodu {
  d: path("M20.5486 3.45154C22.7721 5.67503 22.3734 9.67866 19.816 12.236C17.2585 14.7934 12.3042 16.1425 10.0807 13.9191C7.85713 11.6956 9.20632 6.74143 11.7638 4.18408C14.3212 1.62672 18.325 1.22806 20.5486 3.45154Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxcwdzb9o {
  d: path("M20.5487 3.45138C21.7568 4.65945 19.0986 8.12273 17.3281 9.89321C15.5576 11.6637 11.289 15.127 10.0808 13.9189C8.87273 12.7108 12.3367 8.44291 14.1072 6.67243C15.8778 4.90196 19.3406 2.24331 20.5487 3.45138Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n31o93rng {
  d: path("M12.8991 15.127L6.85994 21.1659C5.74816 22.2777 3.94561 22.2777 2.83383 21.1659C1.72206 20.0542 1.72206 18.2517 2.83383 17.14L8.87299 11.101");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
