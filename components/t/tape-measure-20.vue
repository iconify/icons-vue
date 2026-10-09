<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntlisvb1z.css';
import '../../css/u/u1qifac6a.css';
import '../../css/c/cs4mpneqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ntlisvb1z"/><path class="u1qifac6a"/><path class="cs4mpneqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tape-measure-20" /></template>
