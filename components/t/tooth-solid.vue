<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqil9vbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqil9vbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tooth-solid" /></template>
