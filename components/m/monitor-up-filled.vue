<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e__od32lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e__od32lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-up-filled" /></template>
