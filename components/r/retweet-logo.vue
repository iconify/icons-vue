<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veznnoyuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veznnoyuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:retweet-logo" /></template>
