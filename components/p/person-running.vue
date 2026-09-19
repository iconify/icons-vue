<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kerc9_bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kerc9_bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-running" /></template>
