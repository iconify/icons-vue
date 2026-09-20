<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abwve-4qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abwve-4qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trilium-deprecated-light" /></template>
