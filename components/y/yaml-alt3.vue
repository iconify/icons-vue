<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouarm639k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouarm639k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yaml-alt3" /></template>
