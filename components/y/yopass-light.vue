<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qig4g1byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qig4g1byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yopass-light" /></template>
