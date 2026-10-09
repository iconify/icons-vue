<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkihj-w6g.css';
import '../../css/y/yttd9waod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="yttd9waod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-alert-20" /></template>
