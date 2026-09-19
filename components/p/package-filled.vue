<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3bwd3b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3bwd3b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:package-filled" /></template>
