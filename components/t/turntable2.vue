<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl25cabmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fl25cabmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:turntable2" /></template>
