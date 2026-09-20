<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz78q1_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz78q1_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:xrp" /></template>
