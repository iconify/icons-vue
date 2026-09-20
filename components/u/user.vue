<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/masby1nrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="masby1nrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:user" /></template>
