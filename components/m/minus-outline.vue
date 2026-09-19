<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3bf_1-yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3bf_1-yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:minus-outline" /></template>
