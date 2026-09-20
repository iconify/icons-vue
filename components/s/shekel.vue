<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nol1jj94z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nol1jj94z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shekel" /></template>
