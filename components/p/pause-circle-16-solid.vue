<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4vbgw1nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a4vbgw1nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-circle-16-solid" /></template>
