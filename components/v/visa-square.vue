<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfbenc0fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbenc0fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:visa-square" /></template>
