<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcrkwsbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qcrkwsbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:store-1-solid" /></template>
