<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdd28xodh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdd28xodh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sperm-24px" /></template>
