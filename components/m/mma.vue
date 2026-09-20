<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndny7ndpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndny7ndpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mma" /></template>
