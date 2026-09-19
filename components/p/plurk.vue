<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-63y2w0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":488};
const content = `<path class="l-63y2w0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:plurk" /></template>
