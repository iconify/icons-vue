<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi3a7acyt.css';
import '../../css/b/bjedjv8iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3a7acyt"/><path class="bjedjv8iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:newspaper" /></template>
