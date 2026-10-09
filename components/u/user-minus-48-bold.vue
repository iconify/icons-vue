<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh2_u5bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lh2_u5bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-minus-48-bold" /></template>
