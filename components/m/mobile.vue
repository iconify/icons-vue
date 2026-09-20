<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8wrg7o9z.css';
import '../../css/w/wgxunzb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o8wrg7o9z"/><ellipse class="wgxunzb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:mobile" /></template>
