<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omop2lbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="omop2lbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pictures-folder-memories-solid" /></template>
