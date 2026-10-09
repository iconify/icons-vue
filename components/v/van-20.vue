<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miccwacuq.css';
import '../../css/z/z0q4lw36b.css';
import '../../css/f/f8wc0fbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="miccwacuq"/><path class="z0q4lw36b"/><path class="f8wc0fbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:van-20" /></template>
