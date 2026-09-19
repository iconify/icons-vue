<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8hjx9bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8hjx9bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:quotes-left" /></template>
