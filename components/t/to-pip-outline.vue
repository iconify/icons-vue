<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsyqafb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsyqafb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:to-pip-outline" /></template>
