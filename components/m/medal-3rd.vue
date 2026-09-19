<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ughjblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-ughjblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:medal-3rd" /></template>
