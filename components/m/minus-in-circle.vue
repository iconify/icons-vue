<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxe03ccvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxe03ccvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:minus-in-circle" /></template>
