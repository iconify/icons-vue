<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wya9wt90b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wya9wt90b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:price-tag" /></template>
