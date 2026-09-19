<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq0wx8bxg.css';
import '../../css/l/l6oz6zbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq0wx8bxg"/><path class="l6oz6zbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wallet-alt" /></template>
