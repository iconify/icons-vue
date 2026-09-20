<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft_s7-blo.css';
import '../../css/l/l-9yspb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ft_s7-blo"/><path class="l-9yspb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:up-right-arrow" /></template>
