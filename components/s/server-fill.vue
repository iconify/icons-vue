<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oonysabqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oonysabqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:server-fill" /></template>
