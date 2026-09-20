<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhaym9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhaym9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mountain-2-fill" /></template>
