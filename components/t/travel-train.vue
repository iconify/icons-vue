<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad3lmgbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ad3lmgbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:travel-train" /></template>
