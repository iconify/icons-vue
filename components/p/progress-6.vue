<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv3cf2bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wv3cf2bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-6" /></template>
