<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7drbab-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7drbab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:up-two" /></template>
