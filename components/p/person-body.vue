<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vowu4hbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vowu4hbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:person-body" /></template>
