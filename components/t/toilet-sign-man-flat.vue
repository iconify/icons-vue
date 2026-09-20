<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk9mervdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dk9mervdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:toilet-sign-man-flat" /></template>
