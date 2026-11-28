<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7lmqhk6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7lmqhk6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trapezoid-solid" /></template>
