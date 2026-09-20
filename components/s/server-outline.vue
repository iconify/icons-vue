<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75k15bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e75k15bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-outline" /></template>
