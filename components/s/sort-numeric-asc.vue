<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kic8bacdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kic8bacdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sort-numeric-asc" /></template>
