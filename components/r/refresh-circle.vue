<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk_-i9kqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nk_-i9kqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:refresh-circle" /></template>
