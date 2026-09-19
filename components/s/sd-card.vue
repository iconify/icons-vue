<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubpwl-aai.css';
import '../../css/t/tfo27y8rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubpwl-aai"/><path class="tfo27y8rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sd-card" /></template>
