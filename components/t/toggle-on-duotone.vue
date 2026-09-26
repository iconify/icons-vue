<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4zev7d4r"/><path clip-rule="evenodd" class="j7l35go9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-on-duotone" /></template>
<style>
.b4zev7d4r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 12C19 13.6568 17.6568 15 16 15C14.3432 15 13 13.6568 13 12C13 10.3432 14.3432 9 16 9C17.6568 9 19 10.3432 19 12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j7l35go9m {
  fill-rule: evenodd;
  d: path("M8 5H16C19.866 5 23 8.13401 23 12C23 15.866 19.866 19 16 19H8C4.13401 19 1 15.866 1 12C1 8.13401 4.13401 5 8 5ZM19 12C19 13.6568 17.6568 15 16 15C14.3432 15 13 13.6568 13 12C13 10.3432 14.3432 9 16 9C17.6568 9 19 10.3432 19 12Z");
}

</style>
