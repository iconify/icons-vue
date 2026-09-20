<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2jgq4b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2jgq4b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rocket-line" /></template>
