<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z13_dp0su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z13_dp0su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:on-off-16" /></template>
