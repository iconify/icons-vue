<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb9czabem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb9czabem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stars2" /></template>
