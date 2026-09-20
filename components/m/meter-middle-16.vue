<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6ima4-rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t6ima4-rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:meter-middle-16" /></template>
