<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xia2udbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xia2udbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octobot-dark" /></template>
