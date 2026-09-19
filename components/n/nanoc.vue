<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gowdtxb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gowdtxb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nanoc" /></template>
