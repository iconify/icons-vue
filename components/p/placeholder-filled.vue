<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxre15bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxre15bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:placeholder-filled" /></template>
