<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbmunibji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbmunibji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tag-star" /></template>
