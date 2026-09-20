<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v-lotdbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-28-regular" /></template>
<style>
.v-lotdbtx {
  fill: currentColor;
  d: path("M16.708 5.5H5.754a2.25 2.25 0 0 0-2.25 2.25v.782l10.403 5.328c.323.499.819.886 1.424 1.052l-.99.506a.75.75 0 0 1-.683 0l-10.154-5.2v9.032a2.25 2.25 0 0 0 2.25 2.25H22.25a2.25 2.25 0 0 0 2.25-2.25V15H26v4.25A3.75 3.75 0 0 1 22.25 23H5.754a3.75 3.75 0 0 1-3.75-3.75V7.75A3.75 3.75 0 0 1 5.754 4H17.46zm2.956-3.672c.553-1.104 2.12-1.104 2.672 0l5.002 9.992c.5 1-.222 2.18-1.336 2.18H15.998c-1.114 0-1.837-1.18-1.336-2.18zM21 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5A.5.5 0 0 0 21 4");
}

</style>
