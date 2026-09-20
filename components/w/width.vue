<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amj8daclg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="amj8daclg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:width" /></template>
