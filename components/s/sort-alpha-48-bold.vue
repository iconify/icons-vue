<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixu--sbaj.css';
import '../../css/z/z4gxs_ibg.css';
import '../../css/x/xoi-lebbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixu--sbaj"/><path class="z4gxs_ibg"/><path class="xoi-lebbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-alpha-48-bold" /></template>
