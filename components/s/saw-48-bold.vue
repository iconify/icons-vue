<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzx5mchnl.css';
import '../../css/w/w2wr_lj5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xzx5mchnl"/><path class="w2wr_lj5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saw-48-bold" /></template>
