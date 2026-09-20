<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl9c0ib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yl9c0ib4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pipe-16" /></template>
