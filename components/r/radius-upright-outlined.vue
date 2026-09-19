<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktvmvts2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ktvmvts2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:radius-upright-outlined" /></template>
