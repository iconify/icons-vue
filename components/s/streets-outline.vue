<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_x-b-xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nc_x-b-xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-outline" /></template>
