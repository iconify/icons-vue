<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc4-bsb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tc4-bsb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:share-16" /></template>
