<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw9kfbbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9kfbbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-square-off" /></template>
