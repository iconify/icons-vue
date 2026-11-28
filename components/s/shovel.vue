<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd4r63svn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd4r63svn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shovel" /></template>
