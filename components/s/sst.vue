<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyknwlbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":82,"height":64};
const content = `<path clip-rule="evenodd" class="wyknwlbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sst" /></template>
