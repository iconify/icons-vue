<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf86hnbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf86hnbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sydney-opera-house-line" /></template>
