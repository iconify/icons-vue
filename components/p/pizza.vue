<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2b0vb0m.css';
import '../../css/j/j3pf-l97n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2b0vb0m"/><circle class="j3pf-l97n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:pizza" /></template>
