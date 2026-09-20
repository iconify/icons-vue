<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjcq3m1is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjcq3m1is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:obb" /></template>
