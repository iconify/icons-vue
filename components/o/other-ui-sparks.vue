<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0_0xjbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o0_0xjbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-sparks" /></template>
