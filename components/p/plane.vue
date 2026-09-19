<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgflwv-4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgflwv-4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:plane" /></template>
