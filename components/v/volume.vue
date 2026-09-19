<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmt5tot6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmt5tot6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volume" /></template>
