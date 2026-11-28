<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl7xp8btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl7xp8btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:podcast" /></template>
