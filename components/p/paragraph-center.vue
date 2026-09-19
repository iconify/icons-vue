<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljxyob6qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ljxyob6qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:paragraph-center" /></template>
