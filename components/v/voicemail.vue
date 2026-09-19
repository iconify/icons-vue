<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkvak3bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jkvak3bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:voicemail" /></template>
