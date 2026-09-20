<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-5xqh4-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-5xqh4-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rahoot-dark" /></template>
