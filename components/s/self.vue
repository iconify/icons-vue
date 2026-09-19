<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mel2d5bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mel2d5bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:self" /></template>
