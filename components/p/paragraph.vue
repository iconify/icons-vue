<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_e6fpqvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x_e6fpqvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:paragraph" /></template>
