<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fooidy7tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fooidy7tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:twitter" /></template>
