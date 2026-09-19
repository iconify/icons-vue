<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd97j-b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pd97j-b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:tag" /></template>
