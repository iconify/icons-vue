<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns08hgb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns08hgb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qq-fill" /></template>
