<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7c588_9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7c588_9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:recycle-fill" /></template>
