<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5zr8ubgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5zr8ubgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tableau-light" /></template>
