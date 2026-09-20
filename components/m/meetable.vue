<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph5l2_t_x.css';
import '../../css/i/i70tju1pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ph5l2_t_x"/><path class="i70tju1pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meetable" /></template>
