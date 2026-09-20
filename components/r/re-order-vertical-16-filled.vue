<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d-0qihdyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-vertical-16-filled" /></template>
<style>
.d-0qihdyl {
  fill: currentColor;
  d: path("M9.25 13.25V2.75a.75.75 0 0 1 1.493-.102l.007.102v10.5a.75.75 0 0 1-1.493.102zm-4 0V2.75a.75.75 0 0 1 1.493-.102l.007.102v10.5a.75.75 0 0 1-1.493.102z");
}

</style>
