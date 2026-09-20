<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-s55l-ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-s55l-ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vertical-center-outline" /></template>
