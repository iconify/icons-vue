<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgi5fe4yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pgi5fe4yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tornado" /></template>
