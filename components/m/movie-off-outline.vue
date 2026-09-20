<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg21u9l_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg21u9l_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-off-outline" /></template>
