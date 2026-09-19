<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhadlj53g.css';
import '../../css/d/dake0_b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhadlj53g"/><path class="dake0_b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:mobile-1" /></template>
