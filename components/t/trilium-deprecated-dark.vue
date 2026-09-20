<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgwjst6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abgwjst6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trilium-deprecated-dark" /></template>
