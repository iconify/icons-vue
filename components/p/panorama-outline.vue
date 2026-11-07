<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h73y6wmqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h73y6wmqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-outline" /></template>
