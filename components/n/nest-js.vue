<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7ndexc2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7ndexc2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:nest-js" /></template>
