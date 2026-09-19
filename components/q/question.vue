<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmdxg1bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="tmdxg1bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:question" /></template>
