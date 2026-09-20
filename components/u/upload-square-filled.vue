<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwobapb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwobapb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:upload-square-filled" /></template>
