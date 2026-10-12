<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igr5ktb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igr5ktb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wrench-off-filled" /></template>
