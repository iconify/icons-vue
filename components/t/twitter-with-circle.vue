<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-pt2jepa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t-pt2jepa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:twitter-with-circle" /></template>
