<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7qbbsbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r7qbbsbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-magnet" /></template>
