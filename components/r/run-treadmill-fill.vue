<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkj24espx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkj24espx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:run-treadmill-fill" /></template>
