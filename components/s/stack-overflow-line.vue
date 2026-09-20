<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx001kbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx001kbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stack-overflow-line" /></template>
