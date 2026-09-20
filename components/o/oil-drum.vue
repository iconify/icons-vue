<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lnmdz3bxq"/><path class="k63xzvk9w"/><path class="i2qhnyblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:oil-drum" /></template>
<style>
.i2qhnyblk {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M26 1.128a.873.873 0 0 1-.872.872h-2.256A.873.873 0 0 1 22 1.128V.872c0-.481.391-.872.872-.872h2.256c.481 0 .872.391.872.872z");
}

.k63xzvk9w {
  fill: var(--svg-color--269, #269);
  d: path("M30 3.178a.82.82 0 0 1-.822.822H6.822A.82.82 0 0 1 6 3.178v-.356C6 2.368 6.368 2 6.822 2h22.355c.455 0 .823.368.823.822zm0 11a.82.82 0 0 1-.822.822H6.822A.82.82 0 0 1 6 14.178v-.355c0-.455.368-.823.822-.823h22.355c.455 0 .823.368.823.822zm0 10a.82.82 0 0 1-.822.822H6.822A.82.82 0 0 1 6 24.178v-.355c0-.455.368-.823.822-.823h22.355c.455 0 .823.368.823.822zm0 11a.82.82 0 0 1-.822.822H6.822A.82.82 0 0 1 6 35.178v-.355c0-.455.368-.823.822-.823h22.355c.455 0 .823.368.823.822z");
}

.lnmdz3bxq {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M7 25h22v9H7zm0-11h22v9H7zM7 3h22v10H7z");
}

</style>
