<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6bbd1bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6bbd1bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stop" /></template>
