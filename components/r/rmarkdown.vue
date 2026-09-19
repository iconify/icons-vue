<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd5s6zbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zd5s6zbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rmarkdown" /></template>
