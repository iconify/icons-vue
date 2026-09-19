<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icg1szbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="icg1szbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pill" /></template>
