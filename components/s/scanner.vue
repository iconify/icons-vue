<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awydey58c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awydey58c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scanner" /></template>
