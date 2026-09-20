<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8iz7rbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c8iz7rbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pipeline" /></template>
