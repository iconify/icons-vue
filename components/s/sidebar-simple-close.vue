<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbi79f4ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mbi79f4ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-close" /></template>
