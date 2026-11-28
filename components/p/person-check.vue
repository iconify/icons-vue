<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxl3s1f2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxl3s1f2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:person-check" /></template>
