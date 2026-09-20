<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sirb84lzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sirb84lzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:taco-bell" /></template>
