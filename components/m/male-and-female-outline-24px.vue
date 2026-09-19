<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v129qbbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v129qbbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:male-and-female-outline-24px" /></template>
