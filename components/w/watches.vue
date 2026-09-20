<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj9yp3bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yj9yp3bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:watches" /></template>
