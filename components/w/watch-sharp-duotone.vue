<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4ezfoqsl"/><path clip-rule="evenodd" class="ew0mwxbvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch-sharp-duotone" /></template>
<style>
.b4ezfoqsl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.1172 5L7.5077 1.876C7.5703 1.3755 7.9957 1 8.5 1L15.5 1C16.0043 1 16.4297 1.3755 16.4923 1.876L16.8828 5L18 5C18.5523 5 19 5.4477 19 6L19 18C19 18.5523 18.5523 19 18 19L16.8828 19L16.4923 22.124C16.4297 22.6245 16.0043 23 15.5 23L8.5 23C7.9957 23 7.5703 22.6245 7.5077 22.124L7.1172 19L6 19C5.4477 19 5 18.5523 5 18L5 6C5 5.4477 5.4477 5 6 5L7.1172 5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ew0mwxbvg {
  fill-rule: evenodd;
  d: path("M6 5L18 5C18.5523 5 19 5.4477 19 6L19 18C19 18.5523 18.5523 19 18 19L6 19C5.4477 19 5 18.5523 5 18L5 6C5 5.4477 5.4477 5 6 5Z");
}

</style>
