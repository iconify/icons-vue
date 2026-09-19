<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r84m4t-aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="r84m4t-aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ticket" /></template>
