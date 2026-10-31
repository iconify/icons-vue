<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0_od9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0_od9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mention-fill-round" /></template>
