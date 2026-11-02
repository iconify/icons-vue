<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngcpec5mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngcpec5mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-line" /></template>
