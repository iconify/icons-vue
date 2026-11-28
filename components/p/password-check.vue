<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2chzpsyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2chzpsyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:password-check" /></template>
