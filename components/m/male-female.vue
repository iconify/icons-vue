<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkw82pbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkw82pbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:male-female" /></template>
