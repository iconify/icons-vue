<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao0de2bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ao0de2bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:recycle" /></template>
