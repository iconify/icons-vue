<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-nz38byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x-nz38byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table-in-eaved-gabled-building-with-chimney" /></template>
