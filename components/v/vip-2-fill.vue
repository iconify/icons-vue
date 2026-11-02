<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt3fd0bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt3fd0bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-2-fill" /></template>
