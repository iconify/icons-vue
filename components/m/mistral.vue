<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m96o_vbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m96o_vbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mistral" /></template>
