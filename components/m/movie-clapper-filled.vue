<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxzy3ubzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxzy3ubzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:movie-clapper-filled" /></template>
