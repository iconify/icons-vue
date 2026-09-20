<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7_3dwbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7_3dwbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:row-height-s-outline" /></template>
