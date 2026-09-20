<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgqka1bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgqka1bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:three-d-cube-filled" /></template>
