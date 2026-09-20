<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-3r2wvvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b-3r2wvvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:wrench" /></template>
