<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8piecpte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8piecpte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner4" /></template>
