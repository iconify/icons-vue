<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5gwcb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="th5gwcb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:reverse" /></template>
