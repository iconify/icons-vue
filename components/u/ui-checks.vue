<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogpk27bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ogpk27bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ui-checks" /></template>
