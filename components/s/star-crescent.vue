<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btvzwg_0d.css';
import '../../css/f/f7-f7bvjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btvzwg_0d"/><path class="f7-f7bvjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:star-crescent" /></template>
