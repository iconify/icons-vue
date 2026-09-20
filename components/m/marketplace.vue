<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyctoj_di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lyctoj_di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:marketplace" /></template>
