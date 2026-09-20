<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9c2ncydo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9c2ncydo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-forked-16" /></template>
