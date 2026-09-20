<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jio4_ci7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jio4_ci7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:signboard" /></template>
