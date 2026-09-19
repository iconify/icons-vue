<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-yry3tfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p-yry3tfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:share-alt-square" /></template>
