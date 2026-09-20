<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlp_js4cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlp_js4cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pequeroku-dark" /></template>
