<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kosaz9b_v"/><path class="rsad9abjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kosaz9b_v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.2929 2.5858L21.4142 4.7071C22.1953 5.4882 22.1953 6.7545 21.4142 7.5355L7.5355 21.4142C6.7545 22.1953 5.4882 22.1953 4.7071 21.4142L2.5858 19.2929C1.8047 18.5118 1.8047 17.2455 2.5858 16.4645L16.4645 2.5858C17.2455 1.8047 18.5118 1.8047 19.2929 2.5858Z");
}

.rsad9abjr {
  d: path("M12.5837 6.4665L17.5335 11.4163L7.5355 21.4142C6.7545 22.1953 5.4882 22.1953 4.7071 21.4142L2.5858 19.2929C1.8047 18.5118 1.8047 17.2455 2.5858 16.4645L12.5837 6.4665Z");
}

</style>
