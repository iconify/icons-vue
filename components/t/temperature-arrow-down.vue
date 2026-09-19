<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1edp2nss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="q1edp2nss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-arrow-down" /></template>
