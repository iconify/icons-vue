<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb1elkbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb1elkbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapchat-light" /></template>
