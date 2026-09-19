<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqhwqwbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rqhwqwbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-hook-arrow-small-filled" /></template>
