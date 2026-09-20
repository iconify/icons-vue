<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg2r8uccd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg2r8uccd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-star" /></template>
