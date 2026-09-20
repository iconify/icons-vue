<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aixzugbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aixzugbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-upload" /></template>
