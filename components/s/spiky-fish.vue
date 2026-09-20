<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxk-8hbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bxk-8hbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish" /></template>
