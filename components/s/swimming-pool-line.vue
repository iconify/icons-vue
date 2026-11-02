<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc7_h46hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc7_h46hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:swimming-pool-line" /></template>
