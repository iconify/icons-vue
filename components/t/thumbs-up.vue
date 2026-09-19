<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmoh5dbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zmoh5dbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:thumbs-up" /></template>
