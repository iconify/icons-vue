<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9cynrzbj.css';
import '../../css/w/w6sw46v9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9cynrzbj"/><path class="w6sw46v9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typescript" /></template>
