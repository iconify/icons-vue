<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1w39pq_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1w39pq_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rabbit-solid" /></template>
