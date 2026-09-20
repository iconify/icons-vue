<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxr3ndb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxr3ndb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pencil-off" /></template>
