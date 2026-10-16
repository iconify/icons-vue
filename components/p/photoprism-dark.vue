<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxcfexb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":283.46,"height":283.46};
const content = `<path class="zxcfexb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:photoprism-dark" /></template>
