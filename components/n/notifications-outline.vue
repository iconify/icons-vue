<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjhrfp63w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zjhrfp63w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:notifications-outline" /></template>
