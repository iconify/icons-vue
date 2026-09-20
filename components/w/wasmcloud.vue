<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlkcnt-_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlkcnt-_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wasmcloud" /></template>
