<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-9h9wb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-9h9wb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snowman-solid" /></template>
