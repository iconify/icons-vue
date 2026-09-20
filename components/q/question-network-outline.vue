<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxn07f95d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxn07f95d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:question-network-outline" /></template>
