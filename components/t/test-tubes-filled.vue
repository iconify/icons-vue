<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy7l1ybzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fy7l1ybzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:test-tubes-filled" /></template>
