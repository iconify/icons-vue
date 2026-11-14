<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je7-rtbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je7-rtbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:marker-cluster" /></template>
