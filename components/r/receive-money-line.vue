<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djtj93bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djtj93bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:receive-money-line" /></template>
