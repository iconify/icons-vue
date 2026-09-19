<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrmbpcbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrmbpcbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yacht" /></template>
