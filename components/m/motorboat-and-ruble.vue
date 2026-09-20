<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtqgm_p1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mtqgm_p1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-ruble" /></template>
