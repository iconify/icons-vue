<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba7zxubcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba7zxubcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartphone-check" /></template>
