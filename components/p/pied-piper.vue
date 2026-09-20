<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yci86qb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yci86qb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pied-piper" /></template>
