<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuls9dqno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuls9dqno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:warehouse-solid" /></template>
