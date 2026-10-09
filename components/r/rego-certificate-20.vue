<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwpj83ce.css';
import '../../css/x/x3pmlnn9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xiwpj83ce"/><path class="x3pmlnn9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rego-certificate-20" /></template>
