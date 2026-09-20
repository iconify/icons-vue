<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc8n9fb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="hc8n9fb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:thumbs-down" /></template>
