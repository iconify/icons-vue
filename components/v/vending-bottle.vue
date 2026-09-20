<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4iysw_ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a4iysw_ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-bottle" /></template>
