<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dld_scckh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dld_scckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:presentation" /></template>
