<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5xia0bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z5xia0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-setup-2-16" /></template>
