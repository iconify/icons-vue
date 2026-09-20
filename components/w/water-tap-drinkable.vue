<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfzq4k5vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vfzq4k5vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-tap-drinkable" /></template>
