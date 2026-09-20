<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dafof6oau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dafof6oau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-pound" /></template>
