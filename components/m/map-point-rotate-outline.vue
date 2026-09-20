<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b352nuehy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b352nuehy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-rotate-outline" /></template>
