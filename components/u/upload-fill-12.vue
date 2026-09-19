<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbihz6m0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xbihz6m0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:upload-fill-12" /></template>
