<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw6hzbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw6hzbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:thumb-down-filled" /></template>
