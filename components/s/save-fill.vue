<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmxbadvri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmxbadvri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:save-fill" /></template>
