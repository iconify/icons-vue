<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rej6b4bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rej6b4bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:triangle-filled-16" /></template>
