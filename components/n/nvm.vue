<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckfta7erj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckfta7erj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nvm" /></template>
