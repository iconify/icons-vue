<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cinn4vbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cinn4vbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:roller-solid" /></template>
