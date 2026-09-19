<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jak2suhvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jak2suhvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:motion-vector" /></template>
