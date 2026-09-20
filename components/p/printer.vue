<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2jh-x13v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2jh-x13v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:printer" /></template>
