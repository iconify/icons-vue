<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_yatmezl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a_yatmezl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple" /></template>
