<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhu4i3sbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bhu4i3sbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rectangle-stack-16-solid" /></template>
