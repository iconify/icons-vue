<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnp7o8bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nnp7o8bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sign-and-bench" /></template>
