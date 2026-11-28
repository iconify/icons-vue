<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btymlwd6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btymlwd6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sunset" /></template>
