<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du0py_b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="du0py_b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:present-to-all" /></template>
