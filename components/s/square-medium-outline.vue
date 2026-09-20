<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al9z_qb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al9z_qb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-medium-outline" /></template>
