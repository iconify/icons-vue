<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irw_shbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irw_shbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:search-activity-solid" /></template>
