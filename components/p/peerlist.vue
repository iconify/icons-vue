<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on5x2sbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on5x2sbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:peerlist" /></template>
