<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha7298_1d.css';
import '../../css/w/wieaolbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ha7298_1d"/><path class="wieaolbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:password-20" /></template>
