<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obwoa8b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obwoa8b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:slide-switch" /></template>
