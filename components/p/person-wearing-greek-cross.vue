<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjl3xd-zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qjl3xd-zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-greek-cross" /></template>
