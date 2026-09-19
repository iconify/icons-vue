<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzvwkpb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yzvwkpb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:star-alt" /></template>
