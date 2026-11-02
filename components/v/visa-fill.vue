<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/honvbzb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="honvbzb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:visa-fill" /></template>
