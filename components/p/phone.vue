<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2pee6b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y2pee6b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:phone" /></template>
