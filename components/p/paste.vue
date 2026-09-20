<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdpvm3rmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rdpvm3rmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:paste" /></template>
