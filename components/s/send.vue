<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql5l9lgnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql5l9lgnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:send" /></template>
