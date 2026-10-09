<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq-4s2b4h.css';
import '../../css/k/ko8go1bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vq-4s2b4h"/><path class="ko8go1bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pickaxe-20" /></template>
