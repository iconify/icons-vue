<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y35tlbvnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y35tlbvnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed-dark" /></template>
