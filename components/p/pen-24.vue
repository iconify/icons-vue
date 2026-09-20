<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw1xrovwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="uw1xrovwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pen-24" /></template>
