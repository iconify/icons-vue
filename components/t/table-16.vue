<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oks2q6bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oks2q6bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:table-16" /></template>
