<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koy2ms7jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koy2ms7jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:strikethrough-2" /></template>
