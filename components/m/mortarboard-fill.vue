<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1cd53nrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1cd53nrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mortarboard-fill" /></template>
