<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-872bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ck-872bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish-under-fillet-knife" /></template>
