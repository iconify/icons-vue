<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw41_qb9r.css';
import '../../css/o/o0vpernrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gw41_qb9r"/><path class="o0vpernrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:map-marker" /></template>
