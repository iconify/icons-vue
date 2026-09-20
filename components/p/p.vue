<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd8-kbjvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gd8-kbjvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:p" /></template>
