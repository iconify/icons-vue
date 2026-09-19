<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv6chp-kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6chp-kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:octagon-filled" /></template>
