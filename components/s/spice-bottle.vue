<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jennvdbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jennvdbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spice-bottle" /></template>
