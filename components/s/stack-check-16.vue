<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu8w1z02t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu8w1z02t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stack-check-16" /></template>
