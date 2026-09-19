<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1k0_9_to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1k0_9_to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:smiley-face" /></template>
