<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qds8d4bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qds8d4bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-2-fill" /></template>
