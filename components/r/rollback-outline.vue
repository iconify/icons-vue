<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s73ludb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s73ludb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rollback-outline" /></template>
