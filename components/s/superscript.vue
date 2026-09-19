<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku3qf6bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku3qf6bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:superscript" /></template>
