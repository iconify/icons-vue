<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr-36j6gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-36j6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tag" /></template>
