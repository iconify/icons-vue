<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df4em2bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df4em2bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-bulk-round" /></template>
