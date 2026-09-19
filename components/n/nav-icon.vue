<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kex8uib9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="kex8uib9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nav-icon" /></template>
