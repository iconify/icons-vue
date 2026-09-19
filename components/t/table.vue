<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q233av4wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q233av4wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:table" /></template>
