<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b71c6cbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b71c6cbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:world-2-fill" /></template>
