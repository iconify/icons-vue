<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ow9_bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2ow9_bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:paint-bucket" /></template>
