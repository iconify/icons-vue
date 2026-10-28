<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuomrd10d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uuomrd10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:servicenow" /></template>
