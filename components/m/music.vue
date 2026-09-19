<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvaijbbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvaijbbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:music" /></template>
