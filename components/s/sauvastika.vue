<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zob4dxq5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zob4dxq5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sauvastika" /></template>
