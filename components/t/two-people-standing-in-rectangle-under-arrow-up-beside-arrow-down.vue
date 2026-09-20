<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on3r13bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="on3r13bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-people-standing-in-rectangle-under-arrow-up-beside-arrow-down" /></template>
