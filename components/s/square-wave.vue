<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tliwtbgcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tliwtbgcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-wave" /></template>
