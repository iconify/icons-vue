<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn5ux_btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zn5ux_btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:paintroll" /></template>
