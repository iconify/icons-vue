<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr964_uzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yr964_uzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:personal-management-system-dark" /></template>
