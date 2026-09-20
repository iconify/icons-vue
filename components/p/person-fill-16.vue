<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlaz4-4se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rlaz4-4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-fill-16" /></template>
