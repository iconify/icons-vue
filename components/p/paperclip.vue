<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn6651btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zn6651btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:paperclip" /></template>
