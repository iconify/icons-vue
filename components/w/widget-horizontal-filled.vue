<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mscblln2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mscblln2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:widget-horizontal-filled" /></template>
