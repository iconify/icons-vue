<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3z9ob3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="co3z9ob3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:move-down" /></template>
