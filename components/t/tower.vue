<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx0x-mbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bx0x-mbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tower" /></template>
