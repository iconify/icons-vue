<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2wot4b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="p2wot4b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mail" /></template>
