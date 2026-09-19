<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6d51bbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z6d51bbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:table-header-row" /></template>
