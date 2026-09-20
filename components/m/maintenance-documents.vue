<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_-_c70n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xr_-_c70n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-documents" /></template>
