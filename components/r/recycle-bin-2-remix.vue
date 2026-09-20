<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc5tu7bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rc5tu7bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:recycle-bin-2-remix" /></template>
