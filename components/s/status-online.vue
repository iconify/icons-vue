<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnym00-jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rnym00-jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:status-online" /></template>
