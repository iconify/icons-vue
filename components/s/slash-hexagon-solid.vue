<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtjs7lbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtjs7lbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-hexagon-solid" /></template>
