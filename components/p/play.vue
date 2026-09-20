<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouv-dy3cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv-dy3cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:play" /></template>
