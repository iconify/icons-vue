<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxvbazz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qxvbazz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-stroke-12" /></template>
