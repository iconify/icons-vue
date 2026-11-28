<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8zia5udr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8zia5udr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-star" /></template>
