<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xym376n8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xym376n8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:send-alt-2-filled" /></template>
