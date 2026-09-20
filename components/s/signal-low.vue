<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrrn-2bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrrn-2bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signal-low" /></template>
