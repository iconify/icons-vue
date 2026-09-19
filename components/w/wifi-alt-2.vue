<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pccm1gbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":400};
const content = `<path class="pccm1gbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi-alt-2" /></template>
