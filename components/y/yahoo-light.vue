<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg3v8jk9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rg3v8jk9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yahoo-light" /></template>
