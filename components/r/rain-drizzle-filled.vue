<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-i9tb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si-i9tb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rain-drizzle-filled" /></template>
