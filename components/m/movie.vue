<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkrilib-s.css';
import '../../css/d/dh5-_5bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkrilib-s"/><path clip-rule="evenodd" class="dh5-_5bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:movie" /></template>
