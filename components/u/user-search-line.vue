<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs5wqyzfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs5wqyzfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-search-line" /></template>
