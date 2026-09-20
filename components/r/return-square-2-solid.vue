<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8pc8-bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h8pc8-bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:return-square-2-solid" /></template>
