<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsc05bbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xsc05bbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-stroke-20" /></template>
