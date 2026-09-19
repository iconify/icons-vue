<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe7lh5wmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pe7lh5wmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:page-list-solid" /></template>
