<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdgfzqb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wdgfzqb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:snowflake" /></template>
