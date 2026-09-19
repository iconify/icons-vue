<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-pecr1ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="v-pecr1ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:t" /></template>
