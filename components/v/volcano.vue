<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am01m168f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="am01m168f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:volcano" /></template>
