<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4gwcnb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4gwcnb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wechat-light" /></template>
