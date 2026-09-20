<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrgibklam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrgibklam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minimize-square4-filled" /></template>
