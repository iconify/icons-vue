<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-e40hkos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-e40hkos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warning-shield-solid" /></template>
