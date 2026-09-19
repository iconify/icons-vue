<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvtop3b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvtop3b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:notification-fill-16" /></template>
