<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meya6tb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meya6tb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sphere-shape-solid" /></template>
