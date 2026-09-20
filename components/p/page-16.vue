<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o36wcib6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o36wcib6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-16" /></template>
