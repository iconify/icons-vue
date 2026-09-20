<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wecphb13q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wecphb13q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:old-navy-dark" /></template>
