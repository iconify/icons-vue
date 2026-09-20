<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz5-qd-5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bz5-qd-5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:netherlands-with-capital-star" /></template>
