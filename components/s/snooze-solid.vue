<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw5z3cbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vw5z3cbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:snooze-solid" /></template>
