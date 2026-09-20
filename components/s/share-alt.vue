<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1fslfbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1fslfbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:share-alt" /></template>
