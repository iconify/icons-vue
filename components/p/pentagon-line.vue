<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um713dbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um713dbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pentagon-line" /></template>
