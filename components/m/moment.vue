<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha1ke4byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ha1ke4byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:moment" /></template>
