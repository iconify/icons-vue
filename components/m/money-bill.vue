<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyb7ezbvr.css';
import '../../css/g/g_zlf0bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyb7ezbvr"/><circle class="g_zlf0bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:money-bill" /></template>
