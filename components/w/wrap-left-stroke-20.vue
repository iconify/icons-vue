<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lszk02bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lszk02bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-left-stroke-20" /></template>
