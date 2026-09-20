<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iefj8go1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iefj8go1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rvn" /></template>
