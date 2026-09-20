<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngo_95bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ngo_95bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:shield-2-flat" /></template>
