<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx7qfvbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lx7qfvbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:stop" /></template>
