<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd8qo_zpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qd8qo_zpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ticket" /></template>
