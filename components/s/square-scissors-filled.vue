<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiot7o-sa.css';
import '../../css/p/pabyqgbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiot7o-sa"/><path clip-rule="evenodd" class="pabyqgbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-scissors-filled" /></template>
