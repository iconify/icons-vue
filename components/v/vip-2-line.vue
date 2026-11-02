<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnvyml-_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvyml-_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-2-line" /></template>
