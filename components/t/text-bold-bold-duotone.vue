<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx9l9-clq"/><path class="yfq3bynsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-bold-duotone" /></template>
<style>
.xx9l9-clq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 4.6087C4 2.61567 5.61567 1 7.6087 1H12C15.3137 1 18 3.68629 18 7C18 10.3137 15.3137 13 12 13H4V4.6087ZM7.6087 3C6.72024 3 6 3.72024 6 4.6087V11H12C14.2091 11 16 9.20914 16 7C16 4.79086 14.2091 3 12 3H7.6087Z");
}

.yfq3bynsd {
  fill: currentColor;
  d: path("M4 13V19.9412C4 21.6305 5.36948 23 7.05882 23H14C17.3137 23 20 20.3137 20 17C20 14.4259 18.3791 12.2304 16.1022 11.3786C15.0293 12.3842 13.5866 13 12 13H14C16.2091 13 18 14.7909 18 17C18 19.2091 16.2091 21 14 21H7.05882C6.47405 21 6 20.526 6 19.9412V13H4Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
