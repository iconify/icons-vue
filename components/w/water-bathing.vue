<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awbxz5bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="awbxz5bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:water-bathing" /></template>
