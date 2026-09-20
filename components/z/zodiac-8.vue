<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nym03yq8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nym03yq8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-8" /></template>
