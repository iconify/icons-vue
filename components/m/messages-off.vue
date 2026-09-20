<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb-9ncc1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb-9ncc1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:messages-off" /></template>
