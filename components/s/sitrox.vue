<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj71hlv2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wj71hlv2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sitrox" /></template>
