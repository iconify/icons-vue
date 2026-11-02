<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlt238bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlt238bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mickeymouse-line" /></template>
