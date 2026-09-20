<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhrbr0b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lhrbr0b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-centered-image" /></template>
