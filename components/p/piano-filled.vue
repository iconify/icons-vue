<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0a9c_ain.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a9c_ain"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:piano-filled" /></template>
