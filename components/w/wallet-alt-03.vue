<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsa254b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsa254b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wallet-alt-03" /></template>
