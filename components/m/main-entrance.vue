<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkup8jbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wkup8jbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:main-entrance" /></template>
