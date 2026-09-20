<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj7dycb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zj7dycb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rupee" /></template>
