<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e508-4bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e508-4bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palette-solid" /></template>
