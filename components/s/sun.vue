<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq4fk-cfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zq4fk-cfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sun" /></template>
