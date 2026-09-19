<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twl3sac9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="twl3sac9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-exists-stroke-16" /></template>
