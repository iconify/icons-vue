<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq3nws7ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wq3nws7ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:xing-with-circle" /></template>
