<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3igf4-1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3igf4-1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spoon-knife" /></template>
