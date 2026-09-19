<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yocna9rlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yocna9rlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sort-fill-16" /></template>
