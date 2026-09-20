<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c05xg1fra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c05xg1fra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privatefolio-light" /></template>
