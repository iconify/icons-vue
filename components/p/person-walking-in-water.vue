<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yosf0_bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yosf0_bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-in-water" /></template>
