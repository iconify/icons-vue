<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlv74gbrp.css';
import '../../css/s/snocxdbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlv74gbrp"/><path class="snocxdbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-tasks-bold" /></template>
