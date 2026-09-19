<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq0gxh6nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq0gxh6nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:megaphone-01" /></template>
