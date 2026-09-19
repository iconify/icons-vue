<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoosdlbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":524,"height":512};
const content = `<path class="uoosdlbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:npm-old" /></template>
