<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8eti0ial.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8eti0ial"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:xmark-circle-solid" /></template>
