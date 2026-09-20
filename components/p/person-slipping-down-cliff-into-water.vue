<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js3nu1ssz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="js3nu1ssz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-slipping-down-cliff-into-water" /></template>
