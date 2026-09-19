<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zurlrabfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zurlrabfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-2-square-solid" /></template>
