<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5rx_s2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw5rx_s2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:pen-alt" /></template>
