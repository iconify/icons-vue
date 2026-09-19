<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft08bqkvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ft08bqkvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:youtube" /></template>
