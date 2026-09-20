<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl29uebnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl29uebnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash9-filled" /></template>
