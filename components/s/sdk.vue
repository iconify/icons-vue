<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt65e8btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt65e8btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sdk" /></template>
