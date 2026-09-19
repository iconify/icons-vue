<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl6gumbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1472};
const content = `<path class="wl6gumbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:weibo" /></template>
