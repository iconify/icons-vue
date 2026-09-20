<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebn0rgpcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebn0rgpcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omada" /></template>
