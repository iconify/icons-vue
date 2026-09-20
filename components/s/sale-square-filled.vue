<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7mxl3b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7mxl3b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sale-square-filled" /></template>
