<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iujw47b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iujw47b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:midi-16" /></template>
