<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku88zjgxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ku88zjgxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:reddit" /></template>
