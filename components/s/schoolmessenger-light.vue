<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywnwpqb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywnwpqb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:schoolmessenger-light" /></template>
