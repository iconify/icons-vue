<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2v17h9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ys2v17h9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:print" /></template>
