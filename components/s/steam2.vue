<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j49_occ8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j49_occ8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:steam2" /></template>
