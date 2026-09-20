<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2mng4hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ys2mng4hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pdf-16" /></template>
