<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnhb0ybms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnhb0ybms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:virtualbox-alt" /></template>
