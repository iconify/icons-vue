<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz3rlt3dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz3rlt3dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch3" /></template>
