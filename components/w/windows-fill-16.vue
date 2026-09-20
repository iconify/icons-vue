<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5djr2b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5djr2b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:windows-fill-16" /></template>
