<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcc1i2lqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcc1i2lqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-width-filled" /></template>
