<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5u6ijojj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5u6ijojj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prestashop-light" /></template>
