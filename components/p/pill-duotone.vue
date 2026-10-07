<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u3spwkvfd"/><path class="ckw2-2bmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pill-duotone" /></template>
<style>
.ckw2-2bmx {
  d: path("M7.2699 8.6841L12.2877 3.6664C13.3546 2.5994 14.8017 2 16.3106 2C19.4528 2 22 4.5472 22 7.6894C22 9.1983 21.4006 10.6454 20.3336 11.7123L15.3159 16.7301L7.2699 8.6841Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u3spwkvfd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.2877 3.6664C13.3546 2.5994 14.8017 2 16.3106 2C19.4528 2 22 4.5472 22 7.6894C22 9.1983 21.4006 10.6454 20.3336 11.7123L11.7123 20.3336C10.6454 21.4006 9.1983 22 7.6894 22C4.5472 22 2 19.4528 2 16.3106C2 14.8017 2.5994 13.3546 3.6664 12.2877L12.2877 3.6664Z");
}

</style>
