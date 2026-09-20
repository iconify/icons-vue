<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myetzitsr.css';
import '../../css/f/f46ywubav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myetzitsr"/><path class="f46ywubav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:swap" /></template>
