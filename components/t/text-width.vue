<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uea3qtb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uea3qtb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:text-width" /></template>
