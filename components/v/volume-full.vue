<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/himehxbog.css';
import '../../css/j/jhsk6hp0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="himehxbog"/><path class="jhsk6hp0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:volume-full" /></template>
