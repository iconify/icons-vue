<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3djeb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lw3djeb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:military" /></template>
