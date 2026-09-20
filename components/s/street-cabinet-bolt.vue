<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnqr_2bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lnqr_2bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:street-cabinet-bolt" /></template>
