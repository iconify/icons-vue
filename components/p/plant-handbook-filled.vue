<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m370vb7uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m370vb7uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-handbook-filled" /></template>
