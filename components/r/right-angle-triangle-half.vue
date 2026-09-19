<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbatymjye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbatymjye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:right-angle-triangle-half" /></template>
