<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lal_4cc9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lal_4cc9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitra-light" /></template>
