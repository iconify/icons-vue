<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzlg-u0et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlg-u0et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-off" /></template>
