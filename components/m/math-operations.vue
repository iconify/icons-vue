<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvopj_b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uvopj_b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:math-operations" /></template>
