<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yenf5hr5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yenf5hr5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plane-lock" /></template>
