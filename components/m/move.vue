<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlo_a2b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zlo_a2b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:move" /></template>
