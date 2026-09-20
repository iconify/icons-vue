<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkf-om-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkf-om-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ticket-fill" /></template>
