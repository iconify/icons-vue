<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ohz8stp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n9ohz8stp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:zip-folder" /></template>
