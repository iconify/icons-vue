<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8atb-t8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s8atb-t8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:waste-disposal" /></template>
