<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx4um1rco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vx4um1rco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:paradex" /></template>
