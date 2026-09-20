<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wyzdv0bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-cross-16-regular" /></template>
<style>
.wyzdv0bjp {
  fill: currentColor;
  d: path("M9.25 1c.966 0 1.75.784 1.75 1.75V5h2.25c.966 0 1.75.784 1.75 1.75v2.5A1.75 1.75 0 0 1 13.25 11H11v2.25A1.75 1.75 0 0 1 9.25 15h-2.5A1.75 1.75 0 0 1 5 13.25V11H2.75A1.75 1.75 0 0 1 1 9.25v-2.5C1 5.784 1.784 5 2.75 5H5V2.75C5 1.784 5.784 1 6.75 1zM6 13.25c0 .414.336.75.75.75h2.5a.75.75 0 0 0 .75-.75V11H6zM2.75 6a.75.75 0 0 0-.75.75v2.5c0 .414.336.75.75.75H5V6zM6 10h4V6H6zm5 0h2.25a.75.75 0 0 0 .75-.75v-2.5a.75.75 0 0 0-.75-.75H11zM6.75 2a.75.75 0 0 0-.75.75V5h4V2.75A.75.75 0 0 0 9.25 2z");
}

</style>
