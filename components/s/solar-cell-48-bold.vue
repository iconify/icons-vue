<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-f-m2b4w.css';
import '../../css/a/a5---6bmt.css';
import '../../css/p/p8v8gwqin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-f-m2b4w"/><path class="a5---6bmt"/><path class="p8v8gwqin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-cell-48-bold" /></template>
