<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9-3gcbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d9-3gcbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:microphone" /></template>
