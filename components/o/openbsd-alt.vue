<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6dwxwbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6dwxwbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openbsd-alt" /></template>
