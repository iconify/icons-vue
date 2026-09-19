<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2u9y6bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p2u9y6bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:post" /></template>
