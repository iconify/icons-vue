<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be9f3qbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="be9f3qbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-following" /></template>
