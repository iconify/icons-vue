<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxmw32r0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxmw32r0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:vector-intersection" /></template>
