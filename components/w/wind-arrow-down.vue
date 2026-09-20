<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmc80rbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmc80rbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wind-arrow-down" /></template>
