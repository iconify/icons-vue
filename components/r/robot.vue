<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqg85fbuk.css';
import '../../css/e/e-sveq-za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vqg85fbuk"/><circle class="e-sveq-za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:robot" /></template>
