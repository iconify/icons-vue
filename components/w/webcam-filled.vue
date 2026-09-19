<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz7555nvh.css';
import '../../css/q/q4tdn3ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7555nvh"/><path class="q4tdn3ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:webcam-filled" /></template>
