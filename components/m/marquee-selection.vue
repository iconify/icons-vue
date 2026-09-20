<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qay0ro2fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qay0ro2fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:marquee-selection" /></template>
