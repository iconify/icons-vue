<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_nq_b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nr_nq_b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:squares-below-rectangle" /></template>
