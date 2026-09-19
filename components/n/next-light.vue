<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y30wmue-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="y30wmue-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:next-light" /></template>
