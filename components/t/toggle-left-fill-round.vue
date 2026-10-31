<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag8vmcb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8vmcb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-left-fill-round" /></template>
