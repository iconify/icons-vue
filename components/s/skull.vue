<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d20p71_za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d20p71_za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:skull" /></template>
