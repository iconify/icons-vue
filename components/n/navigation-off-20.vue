<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z90t0b6bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z90t0b6bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-off-20" /></template>
