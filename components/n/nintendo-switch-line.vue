<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soe3d3biv.css';
import '../../css/o/ouvk3bb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soe3d3biv"/><path class="ouvk3bb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nintendo-switch-line" /></template>
