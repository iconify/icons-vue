<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y__pstb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y__pstb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-text-fill" /></template>
