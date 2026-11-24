<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg1bknb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg1bknb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-filled" /></template>
