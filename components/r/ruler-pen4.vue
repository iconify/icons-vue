<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poxikfbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poxikfbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen4" /></template>
