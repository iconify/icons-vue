<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi221rtgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zi221rtgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:networking-toolbox-light" /></template>
