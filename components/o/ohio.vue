<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1fm_tbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z1fm_tbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ohio" /></template>
