<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpnvortse.css';
import '../../css/z/zpkef6b1t.css';
import '../../css/r/roy5ebcho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mpnvortse"/><path class="zpkef6b1t"/><path class="roy5ebcho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warehouse-48-bold" /></template>
