<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5i5oac3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l5i5oac3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:stop-small-16" /></template>
