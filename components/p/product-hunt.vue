<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrn2e5z6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zrn2e5z6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:product-hunt" /></template>
