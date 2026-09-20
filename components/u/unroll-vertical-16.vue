<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzt4jjxuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mzt4jjxuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:unroll-vertical-16" /></template>
