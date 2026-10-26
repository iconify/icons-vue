<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg2o60bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg2o60bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-alt-24px" /></template>
