<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxri2ddjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxri2ddjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:share" /></template>
