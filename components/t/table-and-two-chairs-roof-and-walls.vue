<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf80ehb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mf80ehb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table-and-two-chairs-roof-and-walls" /></template>
