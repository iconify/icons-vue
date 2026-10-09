<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-3bpbzc.css';
import '../../css/y/yck_bwygh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si-3bpbzc"/><path class="yck_bwygh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screwdriver-48" /></template>
