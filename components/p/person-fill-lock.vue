<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz8o_0b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bz8o_0b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-fill-lock" /></template>
