<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn_9tccms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_9tccms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:trees-forest" /></template>
