<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1fw_ybgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fw_ybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:yelp-logo" /></template>
