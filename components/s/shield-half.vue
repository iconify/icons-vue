<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl5_wzbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl5_wzbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shield-half" /></template>
