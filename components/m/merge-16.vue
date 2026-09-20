<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebo_mom1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ebo_mom1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:merge-16" /></template>
