<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c82ie6bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c82ie6bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-circle-fill-12" /></template>
