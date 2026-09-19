<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x71ga5btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x71ga5btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:menu-button-wide-fill" /></template>
