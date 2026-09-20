<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc7iu5jzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yc7iu5jzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:parameter" /></template>
