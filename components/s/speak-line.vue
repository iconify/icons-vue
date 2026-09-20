<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjq3w6t5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjq3w6t5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speak-line" /></template>
