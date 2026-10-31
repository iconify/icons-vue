<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezzw99brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezzw99brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-info-round" /></template>
