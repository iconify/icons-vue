<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv2c6vbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv2c6vbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mop-filled" /></template>
