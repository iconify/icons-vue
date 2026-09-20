<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbp3s3hkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lbp3s3hkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-wall-with-battlement-and-sallyport" /></template>
