<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4cqtxb4q.css';
import '../../css/r/rrw1wrbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4cqtxb4q"/><path class="rrw1wrbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:volume-up" /></template>
