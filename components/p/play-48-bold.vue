<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdpu13b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdpu13b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:play-48-bold" /></template>
