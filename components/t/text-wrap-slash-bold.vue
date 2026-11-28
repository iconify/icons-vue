<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd4hpordp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bd4hpordp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-slash-bold" /></template>
