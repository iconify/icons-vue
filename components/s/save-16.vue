<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb65qtbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tb65qtbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:save-16" /></template>
