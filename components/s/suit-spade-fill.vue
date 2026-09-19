<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc--4bcdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lc--4bcdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suit-spade-fill" /></template>
