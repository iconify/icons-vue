<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2w3jzfpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2w3jzfpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-large-fill-round" /></template>
