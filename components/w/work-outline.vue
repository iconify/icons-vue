<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-qf_91f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-qf_91f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:work-outline" /></template>
