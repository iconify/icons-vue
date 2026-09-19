<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc9rbmb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xc9rbmb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:snort" /></template>
