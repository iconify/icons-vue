<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-jqw2ahc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-jqw2ahc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-moving-01" /></template>
