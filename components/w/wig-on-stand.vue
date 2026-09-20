<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6tu3kpcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f6tu3kpcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:wig-on-stand" /></template>
