<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yro5ksbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yro5ksbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-new-york-times-light" /></template>
