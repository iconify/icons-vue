<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8wimbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gx8wimbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rightward" /></template>
