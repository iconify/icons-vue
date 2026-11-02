<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnt5xlejy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnt5xlejy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-2-line" /></template>
