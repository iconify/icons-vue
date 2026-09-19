<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh3vw6hqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fh3vw6hqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:musical-note-16-solid" /></template>
