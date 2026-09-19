<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fonvkfb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fonvkfb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vyper" /></template>
