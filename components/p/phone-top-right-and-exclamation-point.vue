<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oatpdtb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oatpdtb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-and-exclamation-point" /></template>
