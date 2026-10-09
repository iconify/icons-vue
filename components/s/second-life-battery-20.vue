<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc00mmbgj.css';
import '../../css/d/d99-61b8w.css';
import '../../css/f/f_st51bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pc00mmbgj"/><path class="d99-61b8w"/><path class="f_st51bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:second-life-battery-20" /></template>
