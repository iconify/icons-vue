<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzac1qcfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzac1qcfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tornado-duo" /></template>
