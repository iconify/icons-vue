<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma1gue1oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ma1gue1oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:peerlist-solid" /></template>
