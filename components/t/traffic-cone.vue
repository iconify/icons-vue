<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq7hs77-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fq7hs77-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:traffic-cone" /></template>
