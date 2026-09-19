<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay-av1w0y"/><path class="bf0re0ahk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bed" /></template>
<style>
.ay-av1w0y {
  fill: currentColor;
  d: path("M19 8c0-.55-.45-1-1-1h-4c-.55 0-1 .45-1 1v2h6zm-8 0c0-.55-.45-1-1-1H6c-.55 0-1 .45-1 1v2h6zm8 4H5c-.55 0-1 .45-1 1v2h16v-2c0-.55-.45-1-1-1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bf0re0ahk {
  fill: currentColor;
  d: path("M21 10.78V8c0-1.65-1.35-3-3-3h-4c-.77 0-1.47.3-2 .78c-.53-.48-1.23-.78-2-.78H6C4.35 5 3 6.35 3 8v2.78c-.61.55-1 1.34-1 2.22v6h2v-2h16v2h2v-6c0-.88-.39-1.67-1-2.22M13 8c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v2h-6zM5 8c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v2H5zm15 7H4v-2c0-.55.45-1 1-1h14c.55 0 1 .45 1 1z");
}

</style>
