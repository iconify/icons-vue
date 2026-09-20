<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv-6plbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv-6plbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:refresh-outline" /></template>
