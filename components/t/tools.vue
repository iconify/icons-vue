<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2cv6biat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2cv6biat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tools" /></template>
