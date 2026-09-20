<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_z1ymbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_z1ymbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sd" /></template>
