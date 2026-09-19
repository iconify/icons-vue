<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-22auf4m.css';
import '../../css/h/h2afzob3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-22auf4m"/><path class="h2afzob3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:reload-sharp" /></template>
