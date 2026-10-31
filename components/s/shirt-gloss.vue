<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tghj5bcrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tghj5bcrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shirt-gloss" /></template>
