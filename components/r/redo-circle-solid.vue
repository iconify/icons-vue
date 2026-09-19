<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivvtuz9js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivvtuz9js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:redo-circle-solid" /></template>
