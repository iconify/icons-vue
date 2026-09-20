<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digsqcped.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="digsqcped"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-right-outline" /></template>
