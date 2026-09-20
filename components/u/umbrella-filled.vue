<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3w4lbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp3w4lbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:umbrella-filled" /></template>
