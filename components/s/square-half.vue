<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr8bo8nbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jr8bo8nbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:square-half" /></template>
