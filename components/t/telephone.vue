<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtfe5fs5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vtfe5fs5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:telephone" /></template>
