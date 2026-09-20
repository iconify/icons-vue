<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kii1hnb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kii1hnb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:shamisen-16" /></template>
