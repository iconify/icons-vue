<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwwft199d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwwft199d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:page4" /></template>
