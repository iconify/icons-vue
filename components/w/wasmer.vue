<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxzm8xbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxzm8xbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wasmer" /></template>
