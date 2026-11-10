<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wfm4t2bpw"/><path class="oknb6svcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ring-diamond-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oknb6svcg {
  d: path("M14.062 1C14.323 1.03 14.615 1.17 14.781 1.38L16.781 3.88C17.037 4.2 17.071 4.64 16.868 5L15.31 7.72C14.327 7.29 13.143 7 12 7C10.857 7 9.67 7.29 8.687 7.72L7.132 5C6.928 4.64 6.963 4.2 7.219 3.88L9.252 1.33C9.438 1.15 9.734 1 10 1H14.062Z");
}

.wfm4t2bpw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M12 7C16.418 7 20 10.58 20 15C20 19.42 16.418 23 12 23C7.582 23 4 19.42 4 15C4 10.58 7.582 7 12 7ZM12 9C8.686 9 6 11.69 6 15C6 18.31 8.686 21 12 21C15.314 21 18 18.31 18 15C18 11.69 15.314 9 12 9Z");
}

</style>
