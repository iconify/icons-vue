<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7oswnbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s7oswnbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:toggles" /></template>
