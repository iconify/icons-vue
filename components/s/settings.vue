<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3n-x2bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g3n-x2bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:settings" /></template>
