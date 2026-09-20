<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1m7xcchj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="a1m7xcchj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:menu-cheesburger" /></template>
