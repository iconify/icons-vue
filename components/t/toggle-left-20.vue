<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7u15acll.css';
import '../../css/g/gl6s0rb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7u15acll"/><path class="gl6s0rb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toggle-left-20" /></template>
