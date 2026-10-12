<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt-d5tt_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gt-d5tt_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:signpost-stroke-20" /></template>
