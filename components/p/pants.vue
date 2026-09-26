<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8flxfszn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r8flxfszn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pants" /></template>
