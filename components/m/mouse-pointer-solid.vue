<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwlpnrbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwlpnrbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mouse-pointer-solid" /></template>
