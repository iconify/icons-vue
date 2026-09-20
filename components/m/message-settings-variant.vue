<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3xmjpb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xmjpb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-settings-variant" /></template>
