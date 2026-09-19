<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfxxj0z4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rfxxj0z4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:share-square" /></template>
