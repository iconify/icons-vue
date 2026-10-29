<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uah1xhj4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uah1xhj4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mic-vocal-solid" /></template>
