<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no9pd3psr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="no9pd3psr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sort-alpha-desc" /></template>
