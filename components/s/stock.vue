<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxl2eck4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gxl2eck4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stock" /></template>
