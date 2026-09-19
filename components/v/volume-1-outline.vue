<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r08t_8ogy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r08t_8ogy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:volume-1-outline" /></template>
