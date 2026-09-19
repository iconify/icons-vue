<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5os27n7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y5os27n7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner7" /></template>
