<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iznct4rns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-vertical-24-filled" /></template>
<style>
.iznct4rns {
  fill: currentColor;
  d: path("M18.25 21A2.75 2.75 0 0 0 21 18.25V5.75A2.75 2.75 0 0 0 18.25 3H5.75A2.75 2.75 0 0 0 3 5.75v12.5A2.75 2.75 0 0 0 5.75 21zm-5.75-6.75a.75.75 0 0 1-1.493.102L11 14.25v-7.5a.75.75 0 0 1 1.493-.102l.007.102zm-4-7.5v10.5a.75.75 0 0 1-1.493.102L7 17.25V6.75a.75.75 0 0 1 1.493-.102zm8 10.5a.75.75 0 0 1-1.493.102L15 17.25V6.75a.75.75 0 0 1 1.493-.102l.007.102z");
}

</style>
