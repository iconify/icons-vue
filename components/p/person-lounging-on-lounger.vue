<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7elkzbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f7elkzbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-lounging-on-lounger" /></template>
