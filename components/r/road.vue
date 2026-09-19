<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_4__kbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_4__kbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:road" /></template>
