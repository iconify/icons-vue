<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhgsp_6sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgsp_6sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-box-search" /></template>
