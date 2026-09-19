<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5n7bgbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5n7bgbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-lemniscate-thin" /></template>
