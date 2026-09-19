<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hjnijoblz"/><path class="xqji4h6-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:open-file-folder" /></template>
<style>
.hjnijoblz {
  fill: var(--svg-color--962c2c, #962c2c);
  d: path("M49.3.2L27 8.7s-.8-2-1.5-3.1c-1.7-2.8-4.7-1.9-4.7-1.9l-17 6.1s-2.3 1.1-3.3 4c-.9 2.8 0 6.3 0 6.3l9.8 44l39-37.6S50.6 9.7 51.4 2C51.6-.8 49.3.2 49.3.2");
}

.xqji4h6-o {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("m10.2 64l42.7-33.4s10.6-21.4 11-23c.4-1.8-1.4-1.2-1.4-1.2L39.8 17.1s-1.4 6-4.1 7.6c-3 1.7-17 9.3-17 9.3s-2 1.3-3.1 3.4C14.4 39.5 10.2 64 10.2 64");
}

</style>
