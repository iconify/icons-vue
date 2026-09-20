<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5g4ku_9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5g4ku_9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-slash" /></template>
