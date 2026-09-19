<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd_-5rqcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wd_-5rqcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-clip-16-solid" /></template>
