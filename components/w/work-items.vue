<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxmqw_b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sxmqw_b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-items" /></template>
