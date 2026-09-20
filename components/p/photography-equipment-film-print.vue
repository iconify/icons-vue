<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auvv4vosw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="auvv4vosw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-equipment-film-print" /></template>
