<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2om1gb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n2om1gb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:puzzle" /></template>
