<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1u-aacmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1u-aacmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-navigation-filled" /></template>
