<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqk8hyryo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqk8hyryo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tag-dollar-bold" /></template>
