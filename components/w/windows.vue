<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_a3u6bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_a3u6bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:windows" /></template>
