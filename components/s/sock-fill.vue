<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boi1onnnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boi1onnnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sock-fill" /></template>
