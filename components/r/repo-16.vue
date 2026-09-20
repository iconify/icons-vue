<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg4igib2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gg4igib2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-16" /></template>
