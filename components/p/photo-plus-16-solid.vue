<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3wv0kwij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t3wv0kwij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus-16-solid" /></template>
