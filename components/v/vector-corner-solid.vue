<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alxr3obfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alxr3obfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vector-corner-solid" /></template>
