<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxbs46g8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxbs46g8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sensu" /></template>
