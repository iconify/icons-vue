<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdfztbcra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdfztbcra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stethoscope" /></template>
