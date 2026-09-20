<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1whqkhsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b1whqkhsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:pyramid" /></template>
