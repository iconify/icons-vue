<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbl1pdi-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbl1pdi-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:time-back" /></template>
