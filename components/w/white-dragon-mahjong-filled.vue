<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkt0gbpax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zkt0gbpax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-dragon-mahjong-filled" /></template>
