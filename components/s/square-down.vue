<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk-6h0bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":400};
const content = `<path class="gk-6h0bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:square-down" /></template>
