<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1pv4_b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1pv4_b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:trash-empty" /></template>
