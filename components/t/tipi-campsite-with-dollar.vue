<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wga8-vmxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wga8-vmxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-dollar" /></template>
