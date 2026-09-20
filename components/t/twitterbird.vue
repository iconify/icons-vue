<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wngk6ibgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wngk6ibgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:twitterbird" /></template>
