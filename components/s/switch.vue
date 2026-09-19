<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3qcfitqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":456};
const content = `<path class="u3qcfitqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:switch" /></template>
