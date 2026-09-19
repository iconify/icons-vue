<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwa86wb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rwa86wb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tower" /></template>
