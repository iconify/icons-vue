<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzy6mq1xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzy6mq1xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-star" /></template>
