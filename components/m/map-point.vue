<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzy4r-3vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzy4r-3vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-point" /></template>
