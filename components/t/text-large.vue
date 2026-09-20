<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz00_cbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz00_cbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-large" /></template>
