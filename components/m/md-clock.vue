<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yje01jb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yje01jb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-clock" /></template>
