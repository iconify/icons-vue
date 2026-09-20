<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6mfu1bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6mfu1bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:recycle-line" /></template>
