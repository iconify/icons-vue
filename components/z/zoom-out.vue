<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujkifd7fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujkifd7fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:zoom-out" /></template>
