<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3i_r2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n3i_r2byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-ankh" /></template>
