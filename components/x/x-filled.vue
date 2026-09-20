<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htwjfacjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htwjfacjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:x-filled" /></template>
