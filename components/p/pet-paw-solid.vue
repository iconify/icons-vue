<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qab7zp_yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qab7zp_yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pet-paw-solid" /></template>
