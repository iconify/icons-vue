<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hptsw6dqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hptsw6dqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-yin-yang" /></template>
