<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy2m-lblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qy2m-lblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:pentagon-flat" /></template>
