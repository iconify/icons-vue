<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoqz64bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoqz64bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sleep-off" /></template>
