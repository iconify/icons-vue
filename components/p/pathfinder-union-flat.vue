<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho0idcban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ho0idcban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:pathfinder-union-flat" /></template>
