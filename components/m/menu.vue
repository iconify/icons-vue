<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj8qeqbpz.css';
import '../../css/i/itzm3abxz.css';
import '../../css/y/ycxg46bhx.css';
import '../../css/l/lcqxtqbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer vj8qeqbpz"/><path class="duoicon-secondary-layer itzm3abxz"/><path class="duoicon-primary-layer ycxg46bhx"/><path class="duoicon-secondary-layer lcqxtqbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:menu" /></template>
