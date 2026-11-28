<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3s7s_b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3s7s_b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:play" /></template>
