<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq_bupb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dq_bupb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-activity-filled" /></template>
