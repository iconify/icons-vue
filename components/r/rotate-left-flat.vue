<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4d-inbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v4d-inbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:rotate-left-flat" /></template>
