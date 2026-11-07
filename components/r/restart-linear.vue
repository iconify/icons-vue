<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cad99bcsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cad99bcsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-linear" /></template>
