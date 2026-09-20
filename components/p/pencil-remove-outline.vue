<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0prz-r1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0prz-r1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-remove-outline" /></template>
