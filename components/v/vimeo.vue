<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v41t00byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v41t00byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vimeo" /></template>
