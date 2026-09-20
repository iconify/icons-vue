<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_8q8acdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_8q8acdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nzb-dav-light" /></template>
