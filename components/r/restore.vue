<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr10hmbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dr10hmbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:restore" /></template>
