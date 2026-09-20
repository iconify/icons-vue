<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j056yo54b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j056yo54b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-list" /></template>
