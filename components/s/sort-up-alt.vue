<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km9et_bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="km9et_bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sort-up-alt" /></template>
