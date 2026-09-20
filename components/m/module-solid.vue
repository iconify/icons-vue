<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdqr4db0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdqr4db0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:module-solid" /></template>
