<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5r3apoeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v5r3apoeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-vomiting" /></template>
