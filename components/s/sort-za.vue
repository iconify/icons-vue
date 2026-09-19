<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klz_rcchj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klz_rcchj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:sort-za" /></template>
