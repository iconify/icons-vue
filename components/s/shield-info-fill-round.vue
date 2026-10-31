<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3_31rij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3_31rij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-info-fill-round" /></template>
