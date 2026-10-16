<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moyoz5fkv.css';
import '../../css/b/bxl-xsb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="bxl-xsb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:robot-vacuum-48-bold" /></template>
