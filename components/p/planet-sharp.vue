<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7o0qobko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7o0qobko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:planet-sharp" /></template>
