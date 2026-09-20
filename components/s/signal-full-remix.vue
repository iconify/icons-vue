<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igjfcmbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="igjfcmbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:signal-full-remix" /></template>
