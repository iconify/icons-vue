<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c13zd-d2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c13zd-d2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tumulus" /></template>
