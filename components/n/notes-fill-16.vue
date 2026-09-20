<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-m2kmuut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d-m2kmuut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:notes-fill-16" /></template>
