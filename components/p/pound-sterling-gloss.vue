<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l885mrb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l885mrb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pound-sterling-gloss" /></template>
