<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9y6adcht.css';
import '../../css/e/e5qdz8_wp.css';
import '../../css/l/l4pq8dbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9y6adcht"/><path class="e5qdz8_wp"/><path class="l4pq8dbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tandoor-recipes-dark" /></template>
