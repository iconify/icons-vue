<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_z9bcel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zp_z9bcel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:udder" /></template>
