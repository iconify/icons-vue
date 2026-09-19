<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glcmzy-4i.css';
import '../../css/c/cx7tzdb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="glcmzy-4i"/><path class="cx7tzdb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-circle-stroke-12" /></template>
