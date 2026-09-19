<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc8c-nbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xc8c-nbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:neutral2" /></template>
