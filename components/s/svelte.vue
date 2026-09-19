<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdhb-7r4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":426,"height":512};
const content = `<path class="pdhb-7r4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:svelte" /></template>
