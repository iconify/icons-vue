<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb1vmp6po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bb1vmp6po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:uikit" /></template>
