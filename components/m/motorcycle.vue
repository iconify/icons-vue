<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6h057zgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="i6h057zgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:motorcycle" /></template>
