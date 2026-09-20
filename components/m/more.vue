<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqx-9g47c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqx-9g47c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:more" /></template>
