<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8gytzbiv.css';
import '../../css/n/nigc12pwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g8gytzbiv"/><path class="nigc12pwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:syncpack" /></template>
