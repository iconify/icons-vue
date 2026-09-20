<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj_2pto_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cj_2pto_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mortar-and-pestle-with-greek-cross" /></template>
