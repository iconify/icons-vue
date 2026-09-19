<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4p6ypbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i4p6ypbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pencil-16-solid" /></template>
