<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqvpuqhiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cqvpuqhiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-plus-16-solid" /></template>
