<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf_lw1akt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf_lw1akt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shimmer-outline" /></template>
