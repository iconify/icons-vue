<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7_o1pbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_o1pbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sailboat-solid" /></template>
