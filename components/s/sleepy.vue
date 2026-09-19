<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r78386bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r78386bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sleepy" /></template>
