<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5whqinzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="w5whqinzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:people-arrows-left-right" /></template>
