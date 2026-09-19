<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdy7hybaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vdy7hybaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:steam" /></template>
