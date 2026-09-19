<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnkv8lbiu"/><path class="epdbg_5cz"/><path class="pehdiwj5i"/><path class="cu295uw8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-terminal" /></template>
<style>
.bnkv8lbiu {
  fill: currentColor;
  d: path("M4 18h16V8H4zm8-3h6v2h-6zm-5.91-4.59L7.5 9l4 4l-4 4l-1.41-1.41L8.67 13z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.cu295uw8x {
  fill: currentColor;
  d: path("m7.5 17l4-4l-4-4l-1.41 1.41L8.67 13l-2.58 2.59z");
}

.epdbg_5cz {
  fill: currentColor;
  d: path("M12 15h6v2h-6z");
}

.pehdiwj5i {
  fill: currentColor;
  d: path("M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16c1.1 0 2-.9 2-2V6a2 2 0 0 0-2-2m0 14H4V8h16z");
}

</style>
