<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyy7thb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cyy7thb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plate-wheat" /></template>
