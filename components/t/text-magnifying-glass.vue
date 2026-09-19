<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz9ykdvoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz9ykdvoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:text-magnifying-glass" /></template>
