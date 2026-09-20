<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrg1k343p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrg1k343p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-remove-outline" /></template>
