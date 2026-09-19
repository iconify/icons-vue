<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjtld_bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vjtld_bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sync-to-p-c" /></template>
