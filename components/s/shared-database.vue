<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytseh3-cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ytseh3-cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:shared-database" /></template>
