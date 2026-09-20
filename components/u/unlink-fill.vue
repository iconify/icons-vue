<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhgr8wb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhgr8wb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unlink-fill" /></template>
