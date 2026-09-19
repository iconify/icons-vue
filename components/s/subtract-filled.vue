<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6ja8kb8n.css';
import '../../css/v/v1cwuvwqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6ja8kb8n"/><path class="v1cwuvwqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subtract-filled" /></template>
