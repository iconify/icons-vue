<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzr63ibvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mzr63ibvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rectangle-vertical-rounded-crossed" /></template>
